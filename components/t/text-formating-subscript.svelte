<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifu7oub2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ifu7oub2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:text-formating-subscript" {...props}></Icon>
