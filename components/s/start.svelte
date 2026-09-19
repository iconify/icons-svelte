<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1c7tkr9j.css';
import '../../css/b/bqzzzebfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x1c7tkr9j"/><path class="bqzzzebfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:start" {...props}></Icon>
