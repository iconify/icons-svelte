<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4oochb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j4oochb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:waving-hand-remix" {...props}></Icon>
