<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_mqs0g-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_mqs0g-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:tarteaucitron" {...props}></Icon>
