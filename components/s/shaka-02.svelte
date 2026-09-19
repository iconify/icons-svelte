<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf94p7bjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nf94p7bjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:shaka-02" {...props}></Icon>
