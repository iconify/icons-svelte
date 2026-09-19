<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbfkeibab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbfkeibab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:store-alt" {...props}></Icon>
