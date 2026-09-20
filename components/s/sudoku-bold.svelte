<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thbz86bat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thbz86bat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:sudoku-bold" {...props}></Icon>
