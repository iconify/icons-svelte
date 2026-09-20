<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6-m_kb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o6-m_kb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:trellis-outline" {...props}></Icon>
