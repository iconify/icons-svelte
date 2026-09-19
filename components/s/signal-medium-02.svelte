<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6f32gbni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6f32gbni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:signal-medium-02" {...props}></Icon>
