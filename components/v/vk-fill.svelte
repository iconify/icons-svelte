<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlqn9tbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zlqn9tbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:vk-fill" {...props}></Icon>
