<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/koqv1mtcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="koqv1mtcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sun-set" {...props}></Icon>
