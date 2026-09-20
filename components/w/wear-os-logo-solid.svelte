<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9fct9s_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c9fct9s_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:wear-os-logo-solid" {...props}></Icon>
