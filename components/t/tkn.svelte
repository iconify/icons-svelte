<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ga065kb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ga065kb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:tkn" {...props}></Icon>
