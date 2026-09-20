<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4jpg3bos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4jpg3bos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:select-multiple-solid" {...props}></Icon>
