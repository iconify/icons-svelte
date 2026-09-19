<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpix1x-gj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dpix1x-gj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:slack-fill" {...props}></Icon>
