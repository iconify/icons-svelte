<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4kdf1bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4kdf1bho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-arrow-up-sharp-fill" {...props}></Icon>
