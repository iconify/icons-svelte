<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6t7pi2ud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l6t7pi2ud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:setting-alt-fill" {...props}></Icon>
