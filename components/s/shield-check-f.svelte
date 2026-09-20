<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4m8eac9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-1.5};
const content = `<path class="d4m8eac9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:shield-check-f" {...props}></Icon>
