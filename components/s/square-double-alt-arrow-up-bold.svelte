<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj-k8dbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kj-k8dbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-double-alt-arrow-up-bold" {...props}></Icon>
