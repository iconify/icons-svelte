<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce0dacbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ce0dacbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-caret-up-fill" {...props}></Icon>
