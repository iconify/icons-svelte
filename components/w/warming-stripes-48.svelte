<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjlkw135c.css';
import '../../css/h/hxvilxtxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vjlkw135c"/><path class="hxvilxtxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:warming-stripes-48" {...props}></Icon>
