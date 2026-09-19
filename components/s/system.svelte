<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1l2rin5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1l2rin5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:system" {...props}></Icon>
