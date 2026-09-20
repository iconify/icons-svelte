<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txh3d43br.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txh3d43br"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square" {...props}></Icon>
