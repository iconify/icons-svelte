<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l48dcybie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l48dcybie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:snapdragon-logo-block" {...props}></Icon>
