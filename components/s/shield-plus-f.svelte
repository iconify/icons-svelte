<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3r3ebcls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-1.5};
const content = `<path class="a3r3ebcls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:shield-plus-f" {...props}></Icon>
