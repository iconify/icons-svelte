<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crdisktkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crdisktkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:table-rows-merge-filled" {...props}></Icon>
