<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv7m_e6md.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jv7m_e6md"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shelving-unit-filled" {...props}></Icon>
