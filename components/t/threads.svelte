<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb93m_k3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jb93m_k3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:threads" {...props}></Icon>
