<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj4pa9fcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":448};
const content = `<path class="oj4pa9fcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:virb" {...props}></Icon>
