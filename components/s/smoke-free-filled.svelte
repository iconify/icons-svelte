<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3rx-g4uw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z3rx-g4uw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:smoke-free-filled" {...props}></Icon>
