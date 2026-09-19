<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a93n-smez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a93n-smez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:signal-slash-solid" {...props}></Icon>
