<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anw8c2tnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="anw8c2tnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:text-outline" {...props}></Icon>
