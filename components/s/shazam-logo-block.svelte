<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q06-nox-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q06-nox-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:shazam-logo-block" {...props}></Icon>
