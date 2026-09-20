<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_f_i1b1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j_f_i1b1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:select-all-remix" {...props}></Icon>
