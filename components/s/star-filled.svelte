<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuieg7bdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nuieg7bdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:star-filled" {...props}></Icon>
