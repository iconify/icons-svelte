<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ark3b70lo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ark3b70lo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:tresorit" {...props}></Icon>
