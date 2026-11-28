<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpt93kz6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpt93kz6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tumbler-solid" {...props}></Icon>
