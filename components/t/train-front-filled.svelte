<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aotw5p_wz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aotw5p_wz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:train-front-filled" {...props}></Icon>
