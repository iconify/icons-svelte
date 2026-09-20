<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_h17nbob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_h17nbob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:save-solid" {...props}></Icon>
