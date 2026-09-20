<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba9x64_qo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ba9x64_qo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:user" {...props}></Icon>
