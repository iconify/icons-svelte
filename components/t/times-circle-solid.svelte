<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8fq14a_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8fq14a_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:times-circle-solid" {...props}></Icon>
