<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7kmtli8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-1.5,"top":-1.5};
const content = `<path class="l7kmtli8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:tag-f" {...props}></Icon>
