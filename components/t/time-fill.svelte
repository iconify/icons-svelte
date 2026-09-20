<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da3zc1bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="da3zc1bep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:time-fill" {...props}></Icon>
