<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odqqmdwjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odqqmdwjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:short-pants" {...props}></Icon>
