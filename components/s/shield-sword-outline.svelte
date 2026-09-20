<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_ksqt8zy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_ksqt8zy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shield-sword-outline" {...props}></Icon>
