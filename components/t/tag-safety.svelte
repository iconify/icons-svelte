<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkbhseb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkbhseb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:tag-safety" {...props}></Icon>
