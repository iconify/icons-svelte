<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agxzxbcvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="agxzxbcvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tennis-outline" {...props}></Icon>
