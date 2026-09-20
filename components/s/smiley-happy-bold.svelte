<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beaf8k8ky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="beaf8k8ky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:smiley-happy-bold" {...props}></Icon>
