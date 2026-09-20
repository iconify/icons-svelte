<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anyfb0g-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="anyfb0g-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:turn-right-up" {...props}></Icon>
