<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ziv6hbbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ziv6hbbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sort" {...props}></Icon>
