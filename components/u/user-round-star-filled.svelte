<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r21m_6bay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r21m_6bay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:user-round-star-filled" {...props}></Icon>
