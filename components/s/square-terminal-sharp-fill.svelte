<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubh8lqqcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubh8lqqcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-terminal-sharp-fill" {...props}></Icon>
