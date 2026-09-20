<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvvy5xj8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvvy5xj8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:video-fill" {...props}></Icon>
