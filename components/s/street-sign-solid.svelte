<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgz-nos8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jgz-nos8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:street-sign-solid" {...props}></Icon>
