<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trh7j8bwt.css';
import '../../css/t/tkwuedbzn.css';
import '../../css/s/sifm99blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="trh7j8bwt"/><path class="tkwuedbzn"/><path class="sifm99blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:speaker-wifi-48" {...props}></Icon>
