<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y72idacvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y72idacvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:row-plus-round" {...props}></Icon>
