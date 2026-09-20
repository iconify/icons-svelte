<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_ghwszzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m_ghwszzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:share-circle" {...props}></Icon>
