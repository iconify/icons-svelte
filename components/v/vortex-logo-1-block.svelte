<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6n0jccde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v6n0jccde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:vortex-logo-1-block" {...props}></Icon>
