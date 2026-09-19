<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/por-t0dql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="por-t0dql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:summation-02" {...props}></Icon>
