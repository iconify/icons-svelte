<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tttpw3btv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tttpw3btv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:shirt-sharp" {...props}></Icon>
