<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr4rpnb-k.css';
import '../../css/a/a698f-07m.css';
import '../../css/y/y_7o9gs7y.css';
import '../../css/i/irx0otbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gr4rpnb-k"/><path class="a698f-07m"/><path class="y_7o9gs7y"/><path class="irx0otbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:rubocop" {...props}></Icon>
