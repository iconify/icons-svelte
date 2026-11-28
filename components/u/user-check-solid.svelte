<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzt8uf4ax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzt8uf4ax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:user-check-solid" {...props}></Icon>
