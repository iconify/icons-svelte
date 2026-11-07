<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb5440rgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rb5440rgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:suspension-bolt-outline" {...props}></Icon>
