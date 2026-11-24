<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eagrsqb9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eagrsqb9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ship-cargo-filled" {...props}></Icon>
