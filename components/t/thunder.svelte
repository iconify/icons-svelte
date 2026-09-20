<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4bhd5b_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-6,"top":-2};
const content = `<path class="n4bhd5b_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:thunder" {...props}></Icon>
