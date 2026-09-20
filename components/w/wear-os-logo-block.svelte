<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9-av8bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e9-av8bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:wear-os-logo-block" {...props}></Icon>
