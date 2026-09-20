<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os9ln895c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="os9ln895c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:steps-number-remix" {...props}></Icon>
