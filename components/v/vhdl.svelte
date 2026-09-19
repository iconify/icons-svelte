<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui1beacot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ui1beacot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:vhdl" {...props}></Icon>
