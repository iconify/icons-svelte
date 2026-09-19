<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiwdgmb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aiwdgmb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:shopping-bag-solid" {...props}></Icon>
