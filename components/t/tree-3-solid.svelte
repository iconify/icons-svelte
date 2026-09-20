<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8eqm6bga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k8eqm6bga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:tree-3-solid" {...props}></Icon>
