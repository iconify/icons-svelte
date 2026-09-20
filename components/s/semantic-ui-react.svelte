<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2av1kbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2av1kbms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:semantic-ui-react" {...props}></Icon>
