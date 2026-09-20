<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9cv_w71f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i9cv_w71f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:view-fill" {...props}></Icon>
