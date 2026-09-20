<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj3a1wbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lj3a1wbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:user-plus-solid" {...props}></Icon>
