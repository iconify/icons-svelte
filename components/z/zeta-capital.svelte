<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5kh3sboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5kh3sboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:zeta-capital" {...props}></Icon>
