<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2zno77vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2.5,"top":-6};
const content = `<path class="i2zno77vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:switch-right-f" {...props}></Icon>
