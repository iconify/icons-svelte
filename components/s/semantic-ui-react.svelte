<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmkhx12lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmkhx12lh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:semantic-ui-react" {...props}></Icon>
