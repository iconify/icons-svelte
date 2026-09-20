<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lal5kjbxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lal5kjbxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:ubisoft-logo-solid" {...props}></Icon>
