<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm1m_2hku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm1m_2hku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:select-all" {...props}></Icon>
