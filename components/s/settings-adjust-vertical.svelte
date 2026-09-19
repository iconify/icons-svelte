<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohag08f3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ohag08f3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:settings-adjust-vertical" {...props}></Icon>
