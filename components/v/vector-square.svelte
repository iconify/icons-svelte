<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_1i5p4fg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_1i5p4fg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:vector-square" {...props}></Icon>
