<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-jooqg1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-jooqg1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sun-bright-filled" {...props}></Icon>
