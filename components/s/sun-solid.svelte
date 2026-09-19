<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdm6xblqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdm6xblqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:sun-solid" {...props}></Icon>
