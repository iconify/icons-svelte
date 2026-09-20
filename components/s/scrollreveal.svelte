<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h262zsh8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h262zsh8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:scrollreveal" {...props}></Icon>
