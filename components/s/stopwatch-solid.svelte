<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldn3htbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ldn3htbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:stopwatch-solid" {...props}></Icon>
