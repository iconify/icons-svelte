<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcs7tzbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcs7tzbwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:trash-light" {...props}></Icon>
