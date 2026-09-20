<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq1uwrb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eq1uwrb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:signal-cellular-1-line" {...props}></Icon>
