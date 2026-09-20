<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssj6w-3vo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ssj6w-3vo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:sensitive-solid" {...props}></Icon>
