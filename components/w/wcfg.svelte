<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nom5wvdvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nom5wvdvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:wcfg" {...props}></Icon>
