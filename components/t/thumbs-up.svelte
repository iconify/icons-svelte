<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vli4yubzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vli4yubzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:thumbs-up" {...props}></Icon>
