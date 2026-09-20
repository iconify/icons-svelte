<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6zsho01p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f6zsho01p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:telegram-logo-2-solid" {...props}></Icon>
