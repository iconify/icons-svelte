<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huxb5xbvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="huxb5xbvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:yii" {...props}></Icon>
