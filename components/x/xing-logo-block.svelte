<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es5jyjbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="es5jyjbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:xing-logo-block" {...props}></Icon>
