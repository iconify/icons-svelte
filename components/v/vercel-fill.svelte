<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akipomtzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akipomtzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:vercel-fill" {...props}></Icon>
