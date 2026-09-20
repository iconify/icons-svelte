<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssemfp7-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ssemfp7-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:user-arrows-account-switch-remix" {...props}></Icon>
