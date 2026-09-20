<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a46b-bqkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="a46b-bqkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:shield-half" {...props}></Icon>
