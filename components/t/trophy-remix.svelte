<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1q9jbute.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k1q9jbute"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:trophy-remix" {...props}></Icon>
