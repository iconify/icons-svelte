<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_p24o3jy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z_p24o3jy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:user-feedback-heart-solid" {...props}></Icon>
