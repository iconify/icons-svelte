<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8d05wtmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":24};
const content = `<path class="k8d05wtmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:yen" {...props}></Icon>
