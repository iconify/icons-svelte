<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pllcr1bem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pllcr1bem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:telescope-solid" {...props}></Icon>
