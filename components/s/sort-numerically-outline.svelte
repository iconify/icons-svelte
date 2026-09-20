<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwupjbfpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwupjbfpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:sort-numerically-outline" {...props}></Icon>
