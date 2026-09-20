<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcg52k0qz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hcg52k0qz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:wrench-solid" {...props}></Icon>
