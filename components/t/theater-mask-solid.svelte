<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w72a4dbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w72a4dbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:theater-mask-solid" {...props}></Icon>
