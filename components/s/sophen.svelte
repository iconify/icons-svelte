<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pib_0mbfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pib_0mbfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:sophen" {...props}></Icon>
