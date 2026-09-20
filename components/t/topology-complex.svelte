<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etc7_tbwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etc7_tbwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:topology-complex" {...props}></Icon>
