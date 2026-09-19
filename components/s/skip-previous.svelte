<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn1ytrb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zn1ytrb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:skip-previous" {...props}></Icon>
