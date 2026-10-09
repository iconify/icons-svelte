<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmov8hb-b.css';
import '../../css/m/mn4wyfb1u.css';
import '../../css/a/anwbogkuk.css';
import '../../css/x/xog6z1bwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pmov8hb-b"/><path class="mn4wyfb1u"/><path class="anwbogkuk"/><path class="xog6z1bwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:store-48-bold" {...props}></Icon>
