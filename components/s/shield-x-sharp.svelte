<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdz-ucwkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdz-ucwkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:shield-x-sharp" {...props}></Icon>
