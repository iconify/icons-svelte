<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oexs4c7hr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="oexs4c7hr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:tag-eye" {...props}></Icon>
