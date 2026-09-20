<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkyej1bku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hkyej1bku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-arrow-up-filled" {...props}></Icon>
