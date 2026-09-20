<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz4hwmb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jz4hwmb0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:shield-plus-fill" {...props}></Icon>
